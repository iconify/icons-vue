<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iby16ob0n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="iby16ob0n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:uni597d-box-filled" /></template>

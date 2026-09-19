<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o-_0twbwi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o-_0twbwi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:phone-forwarding-filled" /></template>

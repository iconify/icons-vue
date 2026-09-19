<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kehel7vqs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="kehel7vqs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:uni8349-circled-filled" /></template>

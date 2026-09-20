<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pr_0ps4dh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="pr_0ps4dh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="medical-icon:social-services" /></template>

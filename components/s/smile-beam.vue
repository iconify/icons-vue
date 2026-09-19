<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/um290acwp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":496,"height":512};
const content = `<path class="um290acwp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-regular:smile-beam" /></template>

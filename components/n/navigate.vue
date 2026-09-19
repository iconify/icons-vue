<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kyo5bacyp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kyo5bacyp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:navigate" /></template>

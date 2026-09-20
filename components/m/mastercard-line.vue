<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cjhk_eb_p.css';
import '../../css/k/k5xt08bar.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cjhk_eb_p"/><path class="k5xt08bar"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:mastercard-line" /></template>

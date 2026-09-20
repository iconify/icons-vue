<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xo_l22ipq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xo_l22ipq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uit:wrap-text" /></template>

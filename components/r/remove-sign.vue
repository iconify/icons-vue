<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p_tx9jc_q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1200,"height":1200};
const content = `<path class="p_tx9jc_q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="el:remove-sign" /></template>

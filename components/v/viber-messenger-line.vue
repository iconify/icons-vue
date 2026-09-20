<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zix_86b2w.css';
import '../../css/k/k_1w6h3qx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zix_86b2w"/><path clip-rule="evenodd" class="k_1w6h3qx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:viber-messenger-line" /></template>

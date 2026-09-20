<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kb8k_1dbx.css';
import '../../css/k/k9ywmeb8i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="kb8k_1dbx"/><circle class="k9ywmeb8i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:universal-design" /></template>

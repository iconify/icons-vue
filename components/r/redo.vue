<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/loa53obtg.css';
import '../../css/k/kxhuiabhg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="loa53obtg"/><path class="kxhuiabhg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uim:redo" /></template>

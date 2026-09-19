<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vikf1-blz.css';
import '../../css/n/nt60jabuq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="vikf1-blz"/><path class="nt60jabuq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ei:sc-odnoklassniki" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t6zk_hi4f.css';
import '../../css/k/kwb2ybc3g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="t6zk_hi4f"/><path class="kwb2ybc3g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:namespace-line" /></template>

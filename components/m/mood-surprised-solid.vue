<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nc96cz0xq.css';
import '../../css/j/jx5abbk2w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="nc96cz0xq"/><path clip-rule="evenodd" class="jx5abbk2w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:mood-surprised-solid" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j5yy7fx-i.css';
import '../../css/p/puf8leb7o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="j5yy7fx-i"/><path class="puf8leb7o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:opentofu" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d8ga_xhyw.css';
import '../../css/c/cmxs_qw5o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path transform="matrix(1.26652 0 0 1.26466 -1.313 -1.572)" class="d8ga_xhyw"/><path class="cmxs_qw5o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:rdata" /></template>

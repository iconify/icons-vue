<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qaiyq5bvp.css';
import '../../css/a/a1r6rtrur.css';
import '../../css/l/lraqajimb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g class="qaiyq5bvp"><path class="a1r6rtrur"/><path class="lraqajimb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:ms-powerpoint" /></template>

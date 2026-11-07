<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/edf2mabxb.css';
import '../../css/b/bkvj9ck2i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="edf2mabxb"/><path class="bkvj9ck2i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:square-arrow-right-bold-duotone" /></template>

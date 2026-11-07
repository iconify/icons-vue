<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l6bs4k0fl.css';
import '../../css/i/i6gu3rbfq.css';
import '../../css/z/zxzmymb5g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l6bs4k0fl"/><path class="i6gu3rbfq"/><path class="zxzmymb5g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:pen-new-square-bold-duotone" /></template>

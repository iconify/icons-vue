<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s02m9kbje.css';
import '../../css/p/pcxgyzb-d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s02m9kbje"/><path class="pcxgyzb-d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:wealth-filled" /></template>

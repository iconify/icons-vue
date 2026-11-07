<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nayqy1c_r.css';
import '../../css/i/ir6vxx7sl.css';
import '../../css/l/lquqiwbln.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nayqy1c_r"/><path class="ir6vxx7sl"/><path class="lquqiwbln"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:rows-3-bold-duotone" /></template>

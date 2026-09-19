<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s-_3mcbkz.css';
import '../../css/v/vikdu2bvn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s-_3mcbkz"/><path class="vikdu2bvn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:skateboard" /></template>

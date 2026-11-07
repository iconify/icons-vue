<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j6d250bwp.css';
import '../../css/r/rr_nhybqq.css';
import '../../css/j/jt-vrxbga.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="j6d250bwp"/><path class="rr_nhybqq"/><path clip-rule="evenodd" class="jt-vrxbga"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:user-minus-rounded-outline" /></template>

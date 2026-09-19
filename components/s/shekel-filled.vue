<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j-34vlb0v.css';
import '../../css/t/t38at1bzr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j-34vlb0v"/><path class="t38at1bzr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:shekel-filled" /></template>

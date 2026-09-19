<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u4cgbq-0u.css';
import '../../css/v/vvblkl2ti.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u4cgbq-0u"/><path class="vvblkl2ti"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:wifi-2" /></template>

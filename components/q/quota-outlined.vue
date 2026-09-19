<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g0r9-_bfd.css';
import '../../css/b/bc5_f4bbs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g0r9-_bfd"/><path class="bc5_f4bbs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eos-icons:quota-outlined" /></template>

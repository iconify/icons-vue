<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/smgpfq.css';
import '../../css/s/so-from-62.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="smgpfq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:phone" /></template>

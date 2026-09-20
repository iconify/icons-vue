<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b5j4ppxlp.css';
import '../../css/h/hwyi-sb1a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b5j4ppxlp"/><path class="hwyi-sb1a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:phone-type-bold" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ohl9o5bts.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":13,"height":24};
const content = `<path class="ohl9o5bts"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:yandex-international" /></template>

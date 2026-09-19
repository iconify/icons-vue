<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lruz6gbyv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lruz6gbyv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:menu-alt-04" /></template>

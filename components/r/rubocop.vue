<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r795t1bjv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r795t1bjv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:rubocop" /></template>

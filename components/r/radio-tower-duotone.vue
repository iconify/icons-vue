<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tqwxuxk7i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="primary tqwxuxk7i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:radio-tower-duotone" /></template>

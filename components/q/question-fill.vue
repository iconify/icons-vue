<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zku8iz88p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zku8iz88p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="akar-icons:question-fill" /></template>

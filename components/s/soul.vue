<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c5syj6ckj.css';
import '../../css/t/t5lhdhbbj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c5syj6ckj"/><path class="t5lhdhbbj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:soul" /></template>

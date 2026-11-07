<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/udz5nqb7v.css';
import '../../css/c/cez-1qbcb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="udz5nqb7v"/><path class="cez-1qbcb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:pip-bold" /></template>

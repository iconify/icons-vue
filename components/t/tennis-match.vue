<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k8zxj3bty.css';
import '../../css/m/mg2yoibod.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k8zxj3bty"/><path class="mg2yoibod"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:tennis-match" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/krhh1nj_a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="krhh1nj_a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:radio" /></template>

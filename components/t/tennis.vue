<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cp61lbpnu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cp61lbpnu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gg:tennis" /></template>

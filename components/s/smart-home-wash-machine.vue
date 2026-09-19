<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gr06_6nqb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gr06_6nqb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gg:smart-home-wash-machine" /></template>

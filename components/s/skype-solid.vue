<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hh4byipgz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hh4byipgz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:skype-solid" /></template>

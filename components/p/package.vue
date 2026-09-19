<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n5u0e5usu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="n5u0e5usu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:package" /></template>

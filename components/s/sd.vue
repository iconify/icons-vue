<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/to8u9k8yb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="to8u9k8yb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:sd" /></template>

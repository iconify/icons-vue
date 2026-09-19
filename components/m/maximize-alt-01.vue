<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k2gv-r6vv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="k2gv-r6vv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:maximize-alt-01" /></template>

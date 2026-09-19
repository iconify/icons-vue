<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h9286gj6g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="h9286gj6g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:phone-incoming-forward" /></template>

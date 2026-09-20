<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qn_ogacrd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="qn_ogacrd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pencil:phone" /></template>

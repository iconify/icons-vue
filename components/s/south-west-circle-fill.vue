<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u3pdm5vqk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="u3pdm5vqk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:south-west-circle-fill" /></template>

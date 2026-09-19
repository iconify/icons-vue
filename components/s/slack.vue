<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eecf0ebiw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="eecf0ebiw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gg:slack" /></template>

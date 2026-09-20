<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n2iskrb7m.css';
import '../../css/y/y8vjolbgb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n2iskrb7m"/><path clip-rule="evenodd" class="y8vjolbgb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:table-fill" /></template>

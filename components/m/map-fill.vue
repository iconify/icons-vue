<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/phiqrvb2c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="phiqrvb2c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:map-fill" /></template>

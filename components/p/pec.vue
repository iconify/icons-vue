<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kb-mqnw-t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kb-mqnw-t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:pec" /></template>

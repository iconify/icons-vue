<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pt98fkbcu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pt98fkbcu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:package-minus-sharp" /></template>

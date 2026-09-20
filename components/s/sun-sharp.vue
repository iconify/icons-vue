<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pqt7x9bsk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pqt7x9bsk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:sun-sharp" /></template>

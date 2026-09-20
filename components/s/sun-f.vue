<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rbwbytb9t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-2,"top":-1.5};
const content = `<path class="rbwbytb9t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:sun-f" /></template>

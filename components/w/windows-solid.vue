<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/encrm8bep.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="encrm8bep"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:windows-solid" /></template>

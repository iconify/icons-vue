<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/quqkdstdb.css';
import '../../css/a/a7qf29bcu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="quqkdstdb"/><path class="a7qf29bcu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:square-alt-arrow-up-bold-duotone" /></template>

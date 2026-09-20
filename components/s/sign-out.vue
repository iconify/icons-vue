<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lwj0gbbsy.css';
import '../../css/e/euo04dbov.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lwj0gbbsy"/><path class="euo04dbov"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="prime:sign-out" /></template>

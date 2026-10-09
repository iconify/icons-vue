<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iekkhobgo.css';
import '../../css/a/ahhgx2b3h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="iekkhobgo"/><path class="ahhgx2b3h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:traffic-light-48-bold" /></template>

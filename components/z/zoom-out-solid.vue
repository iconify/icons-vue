<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r4am1db-t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="r4am1db-t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:zoom-out-solid" /></template>

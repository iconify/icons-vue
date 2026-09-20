<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rru8phcei.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rru8phcei"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:math" /></template>

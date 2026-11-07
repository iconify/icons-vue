<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ii1sy95ok.css';
import '../../css/a/au09dfbpz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ii1sy95ok"/><path class="au09dfbpz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:square-academic-cap-bold" /></template>

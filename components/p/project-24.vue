<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ush94023r.css';
import '../../css/l/lb-bssbki.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ush94023r"/><path class="lb-bssbki"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:project-24" /></template>

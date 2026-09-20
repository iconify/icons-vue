<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/krfeep68n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="krfeep68n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:vencord" /></template>

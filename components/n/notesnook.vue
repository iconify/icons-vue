<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g7vo4nbxw.css';
import '../../css/x/x9vltugms.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="g7vo4nbxw"/><path class="x9vltugms"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:notesnook" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j48h6jphd.css';
import '../../css/c/ce756l4cb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<circle class="j48h6jphd"/><path class="ce756l4cb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:whisparr" /></template>

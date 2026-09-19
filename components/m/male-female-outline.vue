<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zmzvefsak.css';
import '../../css/v/v68l-3b8f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<circle class="zmzvefsak"/><path class="v68l-3b8f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:male-female-outline" /></template>

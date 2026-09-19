<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lw5ds4b9n.css';
import '../../css/r/r6--z6kjy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<circle class="lw5ds4b9n"/><path class="r6--z6kjy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:male-outline" /></template>

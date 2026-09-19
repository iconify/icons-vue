<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ylh2tps0c.css';
import '../../css/a/a-5p04cix.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ylh2tps0c"/><path class="a-5p04cix"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:mic-sharp" /></template>

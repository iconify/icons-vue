<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cxqbwqxaq.css';
import '../../css/a/a-5p04cix.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="cxqbwqxaq"/><path class="a-5p04cix"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:mic-sharp" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oh__4bxtl.css';
import '../../css/r/r1xemmb8r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="oh__4bxtl"/><path class="r1xemmb8r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:myheats-dark" /></template>

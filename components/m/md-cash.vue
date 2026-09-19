<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q3cl1ueir.css';
import '../../css/r/r04um0bfu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="q3cl1ueir"/><path class="r04um0bfu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:md-cash" /></template>

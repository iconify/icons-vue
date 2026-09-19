<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z4hnn6fqm.css';
import '../../css/i/i5cu0abur.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="z4hnn6fqm"/><path class="i5cu0abur"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:speakerphone" /></template>

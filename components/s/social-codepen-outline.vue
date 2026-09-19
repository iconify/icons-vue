<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h4ut14voh.css';
import '../../css/j/jinu42run.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="h4ut14voh"/><path class="jinu42run"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:social-codepen-outline" /></template>

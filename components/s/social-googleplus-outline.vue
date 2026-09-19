<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m4rwk7b8u.css';
import '../../css/r/r8fapn48o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="m4rwk7b8u"/><path class="r8fapn48o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:social-googleplus-outline" /></template>

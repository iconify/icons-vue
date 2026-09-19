<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iun5hukdv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1280,"height":1472};
const content = `<path class="iun5hukdv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vs:user-suit-female" /></template>

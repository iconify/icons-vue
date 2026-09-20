<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/ghv3vhomw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="ghv3vhomw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:pedalboard-16" /></template>

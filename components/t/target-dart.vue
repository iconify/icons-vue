<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z2rj0jbjh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="z2rj0jbjh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:target-dart" /></template>

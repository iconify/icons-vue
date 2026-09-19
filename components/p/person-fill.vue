<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l0kbdrbpw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="l0kbdrbpw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:person-fill" /></template>

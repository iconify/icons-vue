<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f1qmkqbpw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="f1qmkqbpw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:money-check-alt" /></template>

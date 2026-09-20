<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ok1z80fpp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ok1z80fpp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:person-wearing-cowboy-hat-holding-coiled-rope" /></template>

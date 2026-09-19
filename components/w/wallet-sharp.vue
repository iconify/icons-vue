<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o-g5sab0v.css';
import '../../css/l/lafymqbeu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="o-g5sab0v"/><path class="lafymqbeu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:wallet-sharp" /></template>

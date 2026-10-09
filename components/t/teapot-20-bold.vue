<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kawbyvyzr.css';
import '../../css/f/fr48pn7bt.css';
import '../../css/s/seuqwvv-o.css';
import '../../css/j/jfn5_8beu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="kawbyvyzr"/><path class="fr48pn7bt"/><path class="seuqwvv-o"/><path class="jfn5_8beu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:teapot-20-bold" /></template>

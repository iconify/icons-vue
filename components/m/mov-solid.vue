<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nbr-kl8vw.css';
import '../../css/j/j7zcxhbcw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="nbr-kl8vw"/><path clip-rule="evenodd" class="j7zcxhbcw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:mov-solid" /></template>

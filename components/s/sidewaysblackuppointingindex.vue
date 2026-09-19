<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/krdoyobux.css';
import '../../css/g/glhekuvna.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="krdoyobux"/><path class="glhekuvna"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:sidewaysblackuppointingindex" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bxuzul_hm.css';
import '../../css/m/mrk6j-xvz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bxuzul_hm"/><path class="mrk6j-xvz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:youtube" /></template>

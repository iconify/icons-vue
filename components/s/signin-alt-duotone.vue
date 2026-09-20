<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wy-vytlwd.css';
import '../../css/h/hs0-l3b6r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wy-vytlwd"/><path class="hs0-l3b6r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:signin-alt-duotone" /></template>

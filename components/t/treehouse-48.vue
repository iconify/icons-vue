<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sw7dxmg3c.css';
import '../../css/b/bn1-6gkhr.css';
import '../../css/w/wep3g8b9u.css';
import '../../css/b/byu7we9hs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="sw7dxmg3c"/><path class="bn1-6gkhr"/><path class="wep3g8b9u"/><path class="byu7we9hs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:treehouse-48" /></template>

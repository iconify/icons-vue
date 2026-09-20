<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z8tws73yk.css';
import '../../css/w/wn5ynabza.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z8tws73yk"/><path class="wn5ynabza"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:signin-light" /></template>

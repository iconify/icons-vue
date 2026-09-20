<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zmtz-erdo.css';
import '../../css/z/z9hdrkb6h.css';
import '../../css/v/vzqbsgpvh.css';
import '../../css/e/e23x2926m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zmtz-erdo"/><path clip-rule="evenodd" class="z9hdrkb6h"/><path class="vzqbsgpvh"/><path clip-rule="evenodd" class="e23x2926m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:portx" /></template>

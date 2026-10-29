<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f25aqb1cu.css';
import '../../css/p/pz3wkb9vt.css';
import '../../css/n/nonzebbze.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f25aqb1cu wm-k"/><path class="pz3wkb9vt wm-a"/><path class="nonzebbze wm-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:reply-all" /></template>

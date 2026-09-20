<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b6b6vpb5x.css';
import '../../css/u/uu-fcqbzw.css';
import '../../css/x/xztz0wb3p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="b6b6vpb5x"/><path class="uu-fcqbzw"/><path class="xztz0wb3p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:pastefy-light" /></template>

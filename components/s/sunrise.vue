<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a2fnftbaj.css';
import '../../css/u/u92ri5qvj.css';
import '../../css/p/pa7le0b0l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="a2fnftbaj"/><path clip-rule="evenodd" class="u92ri5qvj"/><path class="pa7le0b0l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:sunrise" /></template>

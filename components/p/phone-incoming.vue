<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a0m25c.css';
import '../../css/a/ain8nj.css';
import '../../css/d/dsugin.css';
import '../../css/g/g-mogd.css';
import '../../css/s/so-from-62.css';
import '../../css/s/so-to-0.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a0m25c ain8nj"/><path class="a0m25c dsugin"/><path class="a0m25c g-mogd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:phone-incoming" /></template>

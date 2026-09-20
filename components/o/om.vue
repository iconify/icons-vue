<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cayrkvbzs.css';
import '../../css/g/gglns0bzm.css';
import '../../css/y/yuncnkbph.css';
import '../../css/v/vo71evf5d.css';
import '../../css/s/s6tk9vb2f.css';
import '../../css/e/evluucc1b.css';
import '../../css/i/iv6o18bfl.css';
import '../../css/e/e4zfowz9r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="cayrkvbzs"/><path class="gglns0bzm"/><circle class="yuncnkbph"/><path class="vo71evf5d"/><path class="s6tk9vb2f"/><path class="evluucc1b"/><circle class="iv6o18bfl"/><path class="e4zfowz9r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:om" /></template>

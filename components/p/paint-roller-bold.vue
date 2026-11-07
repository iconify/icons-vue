<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rwit5_4bm.css';
import '../../css/a/a6molq-5v.css';
import '../../css/z/z75ed3b-u.css';
import '../../css/b/b4tox8bhm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rwit5_4bm"/><path class="a6molq-5v"/><path class="z75ed3b-u"/><path class="b4tox8bhm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:paint-roller-bold" /></template>

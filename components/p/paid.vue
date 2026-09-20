<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ck1zpvp7z.css';
import '../../css/g/gv5ppo3az.css';
import '../../css/u/u4zjxwbyw.css';
import '../../css/h/hxq4vobqf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ck1zpvp7z"/><path class="gv5ppo3az"/><path class="u4zjxwbyw"/><path class="hxq4vobqf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:paid" /></template>

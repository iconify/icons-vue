<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sl70btbxk.css';
import '../../css/a/ax074xbxc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sl70btbxk"/><path class="ax074xbxc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:wand-duotone" /></template>

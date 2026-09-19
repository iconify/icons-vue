<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n32ndfh3v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n32ndfh3v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:sonos-move" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gwzpwfbbu.css';
import '../../css/r/ri95jlkhc.css';
import '../../css/a/avb8i1b-g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gwzpwfbbu"/><path clip-rule="evenodd" class="ri95jlkhc"/><path class="avb8i1b-g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:mega-eth" /></template>

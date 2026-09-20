<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gn2e4nb2l.css';
import '../../css/t/tr3-hqbzp.css';
import '../../css/z/z9_diac_i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gn2e4nb2l"/><path class="tr3-hqbzp"/><path class="z9_diac_i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:nbt" /></template>

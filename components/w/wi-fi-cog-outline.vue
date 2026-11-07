<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n_vrrliit.css';
import '../../css/n/n-jx8c_mo.css';
import '../../css/p/pb5pipz8a.css';
import '../../css/s/s-wmrubua.css';
import '../../css/d/dyip_gl_j.css';
import '../../css/v/v0yar7wgg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n_vrrliit"/><path class="n-jx8c_mo"/><path class="pb5pipz8a"/><path class="s-wmrubua"/><path clip-rule="evenodd" class="dyip_gl_j"/><path class="v0yar7wgg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:wi-fi-cog-outline" /></template>

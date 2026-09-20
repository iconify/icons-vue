<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xrzvno.css';
import '../../css/y/ydovum.css';
import '../../css/g/ggwg4n.css';
import '../../css/f/fill-to-0.css';
import '../../css/d/d-jkxijw.css';
import '../../css/f/fill-to-0_3.css';
import '../../css/r/r-to-0px.css';
import '../../css/r/r-to-2_5px.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xrzvno ydovum"/><circle class="ggwg4n ydovum"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:map-marker-alt-twotone" /></template>

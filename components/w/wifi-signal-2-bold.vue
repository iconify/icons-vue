<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x9cv03zhd.css';
import '../../css/y/ywys0bcog.css';
import '../../css/m/ma0-lhh3s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x9cv03zhd"/><path class="ywys0bcog"/><path class="ma0-lhh3s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:wifi-signal-2-bold" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ygm273o1e.css';
import '../../css/f/frppt49pm.css';
import '../../css/f/f6krerb0t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ygm273o1e"/><path class="frppt49pm"/><path class="f6krerb0t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:pin-slash-24" /></template>

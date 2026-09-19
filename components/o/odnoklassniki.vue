<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b48oo7bzk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":24};
const content = `<path class="b48oo7bzk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:odnoklassniki" /></template>

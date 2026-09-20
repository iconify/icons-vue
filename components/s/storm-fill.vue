<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bqn0bub3s.css';
import '../../css/l/l44l4kkdh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bqn0bub3s"/><path clip-rule="evenodd" class="l44l4kkdh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:storm-fill" /></template>

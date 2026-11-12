<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y9a9t_3-u.css';
import '../../css/x/xxzjvd64g.css';
import '../../css/f/f8umypbrr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="y9a9t_3-u"/><path class="xxzjvd64g"/><path class="f8umypbrr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:paypal-light" /></template>

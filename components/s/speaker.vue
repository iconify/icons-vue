<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hi_7smg8p.css';
import '../../css/z/za0y9kbbq.css';
import '../../css/b/bmqmgbbve.css';
import '../../css/w/w_wojc56u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hi_7smg8p wm-k"/><path class="wm-a za0y9kbbq"/><path class="bmqmgbbve wm-a"/><path class="w_wojc56u wm-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:speaker" /></template>

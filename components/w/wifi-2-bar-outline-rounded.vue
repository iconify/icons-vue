<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="num4xofal"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:wifi-2-bar-outline-rounded" /></template>
<style>
.num4xofal {
  fill: currentColor;
  d: path("M10.908 19.977q-.446-.446-.446-1.092t.446-1.093T12 17.346t1.092.446t.446 1.093t-.446 1.092t-1.092.446t-1.092-.446M12 13q-1.448 0-2.752.49t-2.33 1.352q-.25.196-.559.2q-.307.004-.52-.21q-.214-.219-.205-.523t.26-.507q1.24-1.07 2.794-1.666q1.552-.597 3.312-.597t3.313.6t2.793 1.669q.25.202.262.507q.013.304-.206.524q-.214.213-.521.206t-.558-.203q-1.027-.861-2.331-1.352Q13.448 13 12 13");
}

</style>

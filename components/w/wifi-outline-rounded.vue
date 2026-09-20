<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rcme-7bih"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:wifi-outline-rounded" /></template>
<style>
.rcme-7bih {
  fill: currentColor;
  d: path("M10.908 19.977q-.446-.446-.446-1.092t.446-1.093T12 17.346t1.092.446t.446 1.093t-.446 1.092t-1.092.446t-1.092-.446m4.405-7.838q1.552.6 2.793 1.669q.25.202.262.507q.013.304-.206.524q-.214.213-.521.206t-.558-.203q-1.027-.861-2.331-1.352Q13.448 13 12 13t-2.752.49t-2.33 1.352q-.25.196-.559.2q-.307.004-.52-.21q-.214-.219-.205-.523t.26-.507q1.24-1.07 2.794-1.666q1.552-.597 3.312-.597t3.313.6m2.363-5.547q2.628 1.054 4.674 2.93q.25.212.266.53q.015.317-.204.537q-.233.232-.55.196q-.318-.035-.587-.262q-1.858-1.667-4.23-2.595T12 7t-5.045.928t-4.23 2.595q-.27.227-.586.263q-.318.035-.55-.197q-.22-.22-.204-.537q.015-.317.265-.53q2.046-1.876 4.674-2.93Q8.952 5.54 12 5.54t5.676 1.053");
}

</style>

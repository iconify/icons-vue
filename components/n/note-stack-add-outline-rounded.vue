<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="csgxg8bkx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:note-stack-add-outline-rounded" /></template>
<style>
.csgxg8bkx {
  fill: currentColor;
  d: path("M8 19.385V9.61q0-.671.475-1.14T9.621 8h9.764q.67 0 1.143.472q.472.472.472 1.144v6.29q0 .323-.13.628q-.132.305-.349.522l-3.465 3.465q-.218.218-.522.348q-.305.131-.628.131h-6.29q-.672 0-1.144-.472T8 19.385M3.025 6.596q-.13-.671.258-1.208t1.06-.669l9.619-1.694q.665-.13 1.2.26q.534.392.676 1.057l.137.833q.048.25-.083.396q-.13.146-.313.177q-.183.03-.347-.06T15 5.346l-.175-.923q-.039-.212-.23-.336T14.17 4L4.52 5.714q-.269.038-.404.25q-.134.211-.096.48l1.827 10.37q.037.194-.073.368t-.304.23q-.213.055-.394-.076t-.217-.346zM9 9.616v9.769q0 .269.173.442t.443.173H16l4-4V9.616q0-.27-.173-.443T19.385 9h-9.77q-.269 0-.442.173T9 9.616M14 15v2.5q0 .214.143.357T14.5 18t.357-.143T15 17.5V15h2.5q.214 0 .357-.143T18 14.5t-.143-.357T17.5 14H15v-2.5q0-.213-.143-.357T14.5 11t-.357.143T14 11.5V14h-2.5q-.213 0-.357.143T11 14.5t.143.357t.357.143z");
}

</style>

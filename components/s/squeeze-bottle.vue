<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="n_40fabhl"/><path class="w25jdzble"/><path class="bps9ogbkj"/><path class="q9aw7k-xr"/><path class="lol55ibkl"/><path class="lo635jxmq"/><path class="aso76tb7l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:squeeze-bottle" /></template>
<style>
.aso76tb7l {
  fill: var(--svg-color--ffe8b6, #ffe8b6);
  d: path("M18 18s-4 4.791-4 7a4 4 0 0 0 8 0c0-2.209-4-7-4-7");
}

.bps9ogbkj {
  fill: var(--svg-color--ffac33, #ffac33);
  d: path("M24 11H12c-5 0-6 21-6 21c0 2.2 1.8 4 4 4h16c2.2 0 4-1.8 4-4c0 0-1-21-6-21");
}

.lo635jxmq {
  fill: var(--svg-color--ffcc4d, #ffcc4d);
  d: path("M23.5 13h-11c-.275 0-.5-.225-.5-.5s.225-.5.5-.5h11c.275 0 .5.225.5.5s-.225.5-.5.5");
}

.lol55ibkl {
  fill: var(--svg-color--99aab5, #99aab5);
  d: path("M8.464 4.464L9 5s1-1 6-1h6c.975 0 1.472-.949 1.496-1.922C21 2.078 19.524 2 15 2c-3.859 0-5.519 1.377-6.536 2.464");
}

.n_40fabhl {
  fill: var(--svg-color--66757f, #66757f);
  d: path("M17 3h2v5h-2z");
}

.q9aw7k-xr {
  fill: var(--svg-color--ccd6dd, #ccd6dd);
  d: path("M8 4s2-4 7-4h6c2 0 2 4 0 4h-6c-5 0-6 1-6 1z");
}

.w25jdzble {
  fill: var(--svg-color--99aab5, #99aab5);
  d: path("M12 12V9c0-1.1.9-2 2-2h8c1.1 0 2 .9 2 2v3z");
}

</style>
